<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwql_sdta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwql_sdta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:currency-shekel-fill" /></template>
