<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kftxfzu5d.css';
import '../../css/d/dwh6i6b0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kftxfzu5d"/><path class="dwh6i6b0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:chhoto-url" /></template>
