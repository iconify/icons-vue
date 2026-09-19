<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ze24i7f5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":442,"height":512};
const content = `<path class="ze24i7f5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:faust" /></template>
