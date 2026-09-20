<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/k-6h5bc3a.css';
import '../../css/s/s3uqygbkb.css';
import '../../css/f/f0u2ylb5l.css';
import '../../css/c/cqj5tpb-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="k-6h5bc3a"/><path class="s3uqygbkb"/><path class="f0u2ylb5l"/><path class="cqj5tpb-u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cart-2-broken" /></template>
