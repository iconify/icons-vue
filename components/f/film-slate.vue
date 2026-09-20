<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvn_bpb7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="vvn_bpb7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:film-slate" /></template>
