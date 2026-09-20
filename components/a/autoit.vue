<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrkrr4jyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qrkrr4jyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:autoit" /></template>
