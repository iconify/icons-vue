<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-ng6m2uq.css';
import '../../css/j/j87piqd4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-ng6m2uq"/><path class="j87piqd4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cheese" /></template>
