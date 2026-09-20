<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8mmxnbiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j8mmxnbiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:ai-chart-bar-filled" /></template>
