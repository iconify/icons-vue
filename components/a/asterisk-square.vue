<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7xpl2p_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t7xpl2p_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:asterisk-square" /></template>
