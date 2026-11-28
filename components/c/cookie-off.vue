<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d70u6rznq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d70u6rznq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:cookie-off" /></template>
