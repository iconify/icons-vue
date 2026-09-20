<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1r71ybup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="s1r71ybup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-nutrition" /></template>
