<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8mimxrbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m8mimxrbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:git" /></template>
