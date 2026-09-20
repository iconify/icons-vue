<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tw3ggguzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tw3ggguzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:at" /></template>
