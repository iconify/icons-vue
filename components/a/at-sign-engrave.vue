<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/v9vofmbba.css';
import '../../css/a/azw_bfr_g.css';
import '../../css/b/bk04fhbuy.css';
import '../../css/a/a7xk9qw1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="v9vofmbba"/><path class="azw_bfr_g wm-shadow"/><path class="bk04fhbuy"/><path class="a7xk9qw1p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:at-sign-engrave" /></template>
