<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ww_f37bpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="ww_f37bpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="marketeq:fire-left" /></template>
