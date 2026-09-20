<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-1zbxbys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-1zbxbys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:door-closed-solid" /></template>
