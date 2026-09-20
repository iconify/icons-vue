<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ks-k9hb1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ks-k9hb1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:close" /></template>
