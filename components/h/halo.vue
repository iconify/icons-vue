<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfcpgc_6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":896};
const content = `<path class="qfcpgc_6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:halo" /></template>
