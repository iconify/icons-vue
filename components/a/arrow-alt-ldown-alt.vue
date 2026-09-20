<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8_9n6byx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a8_9n6byx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:arrow-alt-ldown-alt" /></template>
