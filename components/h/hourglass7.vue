<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bo8ctyb6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="bo8ctyb6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:hourglass7" /></template>
