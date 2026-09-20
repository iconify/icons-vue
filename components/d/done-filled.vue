<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trn3j9qcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="trn3j9qcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:done-filled" /></template>
