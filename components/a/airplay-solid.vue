<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krf7npbdz.css';
import '../../css/m/m3scqya2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="krf7npbdz"/><path class="m3scqya2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:airplay-solid" /></template>
