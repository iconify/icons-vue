<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ex-zxk7mb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ex-zxk7mb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:base-station-2-fill" /></template>
