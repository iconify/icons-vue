<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/nz3qfzbna.css';
import '../../css/k/k-e9vg24e.css';
import '../../css/j/jl9f6f4iq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="nz3qfzbna"/><path class="k-e9vg24e"/><path class="jl9f6f4iq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:audit-02" /></template>
