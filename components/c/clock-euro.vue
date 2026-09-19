<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgcm-dbpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hgcm-dbpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:clock-euro" /></template>
