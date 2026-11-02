<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/de42klgpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="de42klgpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:inbox-2-line" /></template>
