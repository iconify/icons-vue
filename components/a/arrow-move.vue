<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvjs9ibqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yvjs9ibqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:arrow-move" /></template>
