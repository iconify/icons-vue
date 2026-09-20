<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_b94v5bn.css';
import '../../css/f/f7p2cw_yv.css';
import '../../css/r/rkuxmrx9q.css';
import '../../css/n/ndmlhzbky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q_b94v5bn"/><path class="f7p2cw_yv"/><path class="rkuxmrx9q"/><path class="ndmlhzbky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:json-alt-5-fill" /></template>
