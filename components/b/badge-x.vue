<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdz9zybsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pdz9zybsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:badge-x" /></template>
