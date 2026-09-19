<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prhz_2bbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="prhz_2bbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:document" /></template>
