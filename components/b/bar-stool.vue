<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/am-bkj_kg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="am-bkj_kg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bar-stool" /></template>
