<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0ks-cr2h.css';
import '../../css/b/bhg-vwbun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="d0ks-cr2h"/><path class="bhg-vwbun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:emote-neutral" /></template>
