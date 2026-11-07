<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/s_gjrqbti.css';
import '../../css/q/qg2a123rv.css';
import '../../css/j/j8wqpub6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="s_gjrqbti"/><path class="qg2a123rv"/><path class="j8wqpub6c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:align-right-linear" /></template>
