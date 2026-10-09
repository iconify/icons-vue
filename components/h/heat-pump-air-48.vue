<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebdkh4bgw.css';
import '../../css/s/syxl9mb3z.css';
import '../../css/w/wk2dzgbah.css';
import '../../css/w/w-o1i1lbw.css';
import '../../css/b/b-2b-wc7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ebdkh4bgw"/><path class="syxl9mb3z"/><path class="wk2dzgbah"/><path class="w-o1i1lbw"/><path class="b-2b-wc7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heat-pump-air-48" /></template>
