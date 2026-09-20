<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sm217z1po.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sm217z1po"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:book-shelf-line" /></template>
