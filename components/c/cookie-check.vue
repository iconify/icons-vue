<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cofxngbmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cofxngbmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:cookie-check" /></template>
