<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzph_hspk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kzph_hspk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:flow-chart-hierachy" /></template>
