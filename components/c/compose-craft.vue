<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aw2-s_bbh.css';
import '../../css/x/x2s5mg4ls.css';
import '../../css/x/xlvmmucks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="aw2-s_bbh"/><path class="x2s5mg4ls"/><path class="xlvmmucks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:compose-craft" /></template>
