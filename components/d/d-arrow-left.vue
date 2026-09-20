<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zt6tuxrbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zt6tuxrbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:d-arrow-left" /></template>
