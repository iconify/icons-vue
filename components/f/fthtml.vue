<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4h-jy6jc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c4h-jy6jc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:fthtml" /></template>
