<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9ynxqbdc.css';
import '../../css/s/si8s1_bwz.css';
import '../../css/a/a6t8n_bir.css';
import '../../css/t/txm8t4b8e.css';
import '../../css/k/kpffwihmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f9ynxqbdc"/><path class="si8s1_bwz"/><path class="a6t8n_bir"/><path class="txm8t4b8e"/><path class="kpffwihmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:flowise" /></template>
