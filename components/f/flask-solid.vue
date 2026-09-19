<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zkf38lbsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zkf38lbsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:flask-solid" /></template>
