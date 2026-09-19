<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/ds4dt58hw.css';
import '../../css/g/g-js9qb0w.css';
import '../../css/k/kl6dl5bmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ds4dt58hw"/><path class="g-js9qb0w"/><path class="kl6dl5bmn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:forward-message" /></template>
