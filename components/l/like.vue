<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdeuh0_pp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="sdeuh0_pp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:like" /></template>
