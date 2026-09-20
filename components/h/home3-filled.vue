<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t9ql_gb4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t9ql_gb4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:home3-filled" /></template>
