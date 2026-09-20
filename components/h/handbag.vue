<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zo4ww_baw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="zo4ww_baw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:handbag" /></template>
