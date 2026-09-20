<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_c89sjru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_c89sjru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:kucoin" /></template>
