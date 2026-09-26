<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/nzhoqcmml.css';
import '../../css/v/v9gqdsvmm.css';
import '../../css/c/cfxd4se9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="nzhoqcmml"/><path class="v9gqdsvmm"/><path class="cfxd4se9w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chevron-first-broken" /></template>
