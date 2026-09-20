<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljbnwqb3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ljbnwqb3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:currency-pound-fill" /></template>
