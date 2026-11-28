<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/id681_wzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="id681_wzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:car-off" /></template>
