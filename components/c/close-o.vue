<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebldvkbho.css';
import '../../css/o/ok5a-4evb.css';
import '../../css/s/skzxnomci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="ebldvkbho"/><path class="ok5a-4evb"/><path class="skzxnomci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:close-o" /></template>
