<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzj0jobev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="nzj0jobev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:calender" /></template>
