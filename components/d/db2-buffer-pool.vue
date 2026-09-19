<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwcqqit1h.css';
import '../../css/c/cpstsachi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mwcqqit1h"/><path class="cpstsachi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:db2-buffer-pool" /></template>
