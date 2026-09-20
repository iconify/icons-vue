<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdkb1-t-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kdkb1-t-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:link" /></template>
