<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qapmv16xh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qapmv16xh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:bellring-off-filled" /></template>
