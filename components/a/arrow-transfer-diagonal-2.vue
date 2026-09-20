<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s03g3-7yd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="s03g3-7yd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:arrow-transfer-diagonal-2" /></template>
