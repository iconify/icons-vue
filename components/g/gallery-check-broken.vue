<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/l60a6dbzb.css';
import '../../css/l/lgbc9yk3h.css';
import '../../css/q/qw59k8t0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="l60a6dbzb"/><path class="lgbc9yk3h"/><path class="qw59k8t0z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:gallery-check-broken" /></template>
