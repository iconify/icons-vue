<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1mcems0k.css';
import '../../css/z/zgr1s6bag.css';
import '../../css/q/q9re1fbbm.css';
import '../../css/p/p40y-2b1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l1mcems0k"/><path class="zgr1s6bag"/><path class="q9re1fbbm"/><path class="p40y-2b1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:house-snowflake-20-bold" /></template>
