<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bov0584ws.css';
import '../../css/p/pcybz4e1f.css';
import '../../css/s/skc1clb-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bov0584ws"/><path class="pcybz4e1f"/><path class="skc1clb-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fli-so" /></template>
