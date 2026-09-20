<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwvt3-eti.css';
import '../../css/y/ybcb2abco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gwvt3-eti"/><path class="ybcb2abco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cat-line" /></template>
