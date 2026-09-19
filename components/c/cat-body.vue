<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4iudzo1t.css';
import '../../css/t/txqx25ycu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t4iudzo1t"/><path class="txqx25ycu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cat-body" /></template>
