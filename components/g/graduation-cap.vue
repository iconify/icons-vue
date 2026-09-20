<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wzutfdbcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wzutfdbcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:graduation-cap" /></template>
