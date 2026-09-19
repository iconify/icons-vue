<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgqc2vbzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgqc2vbzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:infinity" /></template>
