<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s708hktzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s708hktzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:add-circle-sharp" /></template>
