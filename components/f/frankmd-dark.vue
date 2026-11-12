<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snaubdbur.css';
import '../../css/k/k3cps1u4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="snaubdbur"/><path class="k3cps1u4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:frankmd-dark" /></template>
