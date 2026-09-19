<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dre4csbgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b dre4csbgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:flask-round" /></template>
