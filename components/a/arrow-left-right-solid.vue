<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pccykjbqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pccykjbqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:arrow-left-right-solid" /></template>
