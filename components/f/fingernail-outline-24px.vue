<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtw2qxriw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qtw2qxriw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:fingernail-outline-24px" /></template>
