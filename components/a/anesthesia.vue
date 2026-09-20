<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfuwwhbkc.css';
import '../../css/c/c82mu65xq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":63,"height":64};
const content = `<path class="lfuwwhbkc"/><path class="c82mu65xq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:anesthesia" /></template>
