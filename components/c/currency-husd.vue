<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-6_nfb7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-6_nfb7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:currency-husd" /></template>
