<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t24hzt7cl.css';
import '../../css/j/jel44xajw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t24hzt7cl"/><path class="jel44xajw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:link-filled" /></template>
