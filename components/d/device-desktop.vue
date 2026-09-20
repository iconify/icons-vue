<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7u4yomqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m7u4yomqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:device-desktop" /></template>
