<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6bk4pu6o.css';
import '../../css/j/j7r8t5bzq.css';
import '../../css/g/gu8gak4xx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n6bk4pu6o"/><rect class="j7r8t5bzq"/><rect class="gu8gak4xx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:between-horizontal-end-filled" /></template>
