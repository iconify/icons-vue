<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q39l404xn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q39l404xn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:check-light" /></template>
