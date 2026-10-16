<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lnygumoma.css';
import '../../css/m/m_7duebkv.css';
import '../../css/h/ht_ws6k_w.css';
import '../../css/g/gkdo6zoja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lnygumoma"/><path class="m_7duebkv"/><path class="ht_ws6k_w"/><path class="gkdo6zoja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:district-cooling-20-bold" /></template>
