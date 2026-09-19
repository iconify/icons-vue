<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ic6wf_bti.css';
import '../../css/h/h-x55eb4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ic6wf_bti"/><path class="h-x55eb4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:americasglobe" /></template>
