<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myew_qb4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="myew_qb4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:bouncebit" /></template>
