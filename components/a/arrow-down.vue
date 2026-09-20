<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sw64edj9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sw64edj9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:arrow-down" /></template>
