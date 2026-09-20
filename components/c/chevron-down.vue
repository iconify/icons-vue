<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpwd9l.css';
import '../../css/s/so-from-12.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qpwd9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:chevron-down" /></template>
