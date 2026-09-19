<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfz3w9lrl.css';
import '../../css/i/iq03fbgcg.css';
import '../../css/t/tzwzvh3jp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="yfz3w9lrl"/><path class="iq03fbgcg"/><path class="tzwzvh3jp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-street-view" /></template>
