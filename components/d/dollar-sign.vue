<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqto-hbxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aqto-hbxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:dollar-sign" /></template>
