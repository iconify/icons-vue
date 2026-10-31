<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbk-l7bpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbk-l7bpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:asterisk-round" /></template>
