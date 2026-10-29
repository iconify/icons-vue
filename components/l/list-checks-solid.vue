<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/un9kppxfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="un9kppxfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:list-checks-solid" /></template>
