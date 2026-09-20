<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1rk4yuft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b1rk4yuft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:grip-vertical" /></template>
