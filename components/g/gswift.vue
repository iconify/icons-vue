<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okeha2n_r.css';
import '../../css/e/e8h9khb5x.css';
import '../../css/q/quzt27byr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="okeha2n_r"/><path class="e8h9khb5x"/><path class="quzt27byr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:gswift" /></template>
