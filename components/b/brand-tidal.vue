<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzaqddcpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nzaqddcpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-tidal" /></template>
