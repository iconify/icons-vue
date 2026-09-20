<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-171nr1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-171nr1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:left-indent-alt" /></template>
