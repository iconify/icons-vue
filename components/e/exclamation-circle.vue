<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_ma8083f.css';
import '../../css/v/vla37tbfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_ma8083f"/><path class="vla37tbfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:exclamation-circle" /></template>
