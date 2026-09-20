<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpqj49bsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vpqj49bsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:file-text" /></template>
