<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pz3-xgbbc.css';
import '../../css/l/lw8ky0vfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pz3-xgbbc"/><path class="lw8ky0vfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:banknotedollar" /></template>
