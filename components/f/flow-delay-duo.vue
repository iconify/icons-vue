<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xb33x3b4v.css';
import '../../css/h/hs1_ig4jg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary xb33x3b4v"/><path class="hs1_ig4jg primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:flow-delay-duo" /></template>
