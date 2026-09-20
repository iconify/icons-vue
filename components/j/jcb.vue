<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tiar6ybcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tiar6ybcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:jcb" /></template>
