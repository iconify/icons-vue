<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpbvs9qry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qpbvs9qry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:eyebrow-fill" /></template>
