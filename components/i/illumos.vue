<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exom9fblv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":394,"height":512};
const content = `<path class="exom9fblv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:illumos" /></template>
