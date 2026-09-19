<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwpk_5b-d.css';
import '../../css/g/guwa6_8ak.css';
import '../../css/v/v_sn19bay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="zwpk_5b-d"/><path class="guwa6_8ak"/><path class="v_sn19bay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:cloudflare" /></template>
