<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2atjnb_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":26};
const content = `<path class="y2atjnb_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:file-error-26" /></template>
