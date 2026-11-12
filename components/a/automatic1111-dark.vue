<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2y5mgk4u.css';
import '../../css/x/xnlpiqbcd.css';
import '../../css/b/bwk89nrhx.css';
import '../../css/f/f--nfqx9d.css';
import '../../css/q/q_pit_2ju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i2y5mgk4u"/><path class="xnlpiqbcd"/><path class="bwk89nrhx"/><path class="f--nfqx9d"/><path class="q_pit_2ju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:automatic1111-dark" /></template>
