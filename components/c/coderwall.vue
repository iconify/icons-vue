<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvpp2bcjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bvpp2bcjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:coderwall" /></template>
