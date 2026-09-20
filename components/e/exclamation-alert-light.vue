<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kl82r-bam.css';
import '../../css/v/v9y5wi_ot.css';
import '../../css/q/q_ma8083f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kl82r-bam"/><path class="v9y5wi_ot"/><path class="q_ma8083f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:exclamation-alert-light" /></template>
