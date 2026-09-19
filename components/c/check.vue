<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3vcqe0nu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v3vcqe0nu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:check" /></template>
