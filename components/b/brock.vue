<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hr205bcmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hr205bcmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:brock" /></template>
