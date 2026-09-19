<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xz_zxo7ox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xz_zxo7ox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:iata" /></template>
