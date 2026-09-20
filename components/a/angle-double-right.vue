<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ev5fk9umj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ev5fk9umj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:angle-double-right" /></template>
