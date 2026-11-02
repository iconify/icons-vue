<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qu2ws9tix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qu2ws9tix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:lollipop-line" /></template>
