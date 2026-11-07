<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/b/b9hwg5m9c.css';
import '../../css/i/ihjyqm_3u.css';
import '../../css/b/bbto15hdo.css';
import '../../css/i/inol7c_ew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="b9hwg5m9c"/><path class="ihjyqm_3u"/><path class="bbto15hdo"/><path class="inol7c_ew"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:call-medicine-broken" /></template>
