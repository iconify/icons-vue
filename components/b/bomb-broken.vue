<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/a/aa_n4rjmb.css';
import '../../css/m/m99yuxjsm.css';
import '../../css/n/n8llc_q5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="aa_n4rjmb"/><path class="m99yuxjsm"/><path class="n8llc_q5p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bomb-broken" /></template>
