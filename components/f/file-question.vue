<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncwsyc6me.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ncwsyc6me"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:file-question" /></template>
