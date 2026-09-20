<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zm04citcf.css';
import '../../css/k/ke05x4qzq.css';
import '../../css/m/mnll-hb2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zm04citcf"/><path class="ke05x4qzq"/><path class="mnll-hb2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cloudflare-zero-trust" /></template>
