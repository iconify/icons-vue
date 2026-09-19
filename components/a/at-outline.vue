<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ss_nhe6tp.css';
import '../../css/t/trav0txtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ss_nhe6tp"/><path class="trav0txtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:at-outline" /></template>
