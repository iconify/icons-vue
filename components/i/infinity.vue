<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qszbamb4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qszbamb4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:infinity" /></template>
