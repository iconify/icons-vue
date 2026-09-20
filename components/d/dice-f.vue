<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vt-79abhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vt-79abhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:dice-f" /></template>
