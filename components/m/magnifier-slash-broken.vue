<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/c5cjgzbpf.css';
import '../../css/x/x09loybdy.css';
import '../../css/k/k9eq3dbyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="c5cjgzbpf"/><path class="x09loybdy"/><path class="k9eq3dbyp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:magnifier-slash-broken" /></template>
