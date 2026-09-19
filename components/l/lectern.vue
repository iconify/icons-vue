<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/b/b1h85pbcc.css';
import '../../css/b/b5k1ulb5x.css';
import '../../css/q/q_vv9aczd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="b1h85pbcc"/><path class="b5k1ulb5x"/><path class="q_vv9aczd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:lectern" /></template>
