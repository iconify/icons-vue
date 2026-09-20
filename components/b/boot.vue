<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqy0o8b5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="hqy0o8b5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:boot" /></template>
