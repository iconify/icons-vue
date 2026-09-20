<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjnvnmevq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hjnvnmevq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:icq-logo-1-block" /></template>
