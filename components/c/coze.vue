<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0j2kb17q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o0j2kb17q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:coze" /></template>
