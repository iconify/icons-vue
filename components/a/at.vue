<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8lv_jb2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":751,"height":785};
const content = `<path class="z8lv_jb2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:at" /></template>
