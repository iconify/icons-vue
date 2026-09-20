<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/ql_242uqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ql_242uqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:http-que" /></template>
