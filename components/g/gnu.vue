<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grbvkybfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="grbvkybfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:gnu" /></template>
