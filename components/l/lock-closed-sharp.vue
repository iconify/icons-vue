<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ge1z230cx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ge1z230cx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:lock-closed-sharp" /></template>
