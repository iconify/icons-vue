<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_li8cc6d.css';
import '../../css/t/t9ck36orq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_li8cc6d"/><path class="t9ck36orq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:clock-seven" /></template>
