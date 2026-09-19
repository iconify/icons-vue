<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1td-_zdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1td-_zdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:club" /></template>
