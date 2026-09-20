<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/si_mtzbvj.css';
import '../../css/b/bz9swpb3x.css';
import '../../css/n/n0kyqub_b.css';
import '../../css/g/gogond7uq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="si_mtzbvj"/><path class="bz9swpb3x"/><path class="n0kyqub_b"/><path class="gogond7uq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cardholder-broken" /></template>
