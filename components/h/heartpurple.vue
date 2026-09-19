<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzjgi_bqf.css';
import '../../css/d/dx1vlmbja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kzjgi_bqf"/><path class="dx1vlmbja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:heartpurple" /></template>
