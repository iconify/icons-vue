<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ko_s50v2q.css';
import '../../css/k/k0au53bzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ko_s50v2q"/><path class="k0au53bzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:laudspeaker" /></template>
