<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7c4zjbcd.css';
import '../../css/d/dfc4wub2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d7c4zjbcd"/><path class="dfc4wub2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-calendar-heart" /></template>
