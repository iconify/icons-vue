<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjtlbw2qm.css';
import '../../css/d/dlomshbcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":238.125,"height":238.125};
const content = `<circle class="bjtlbw2qm"/><path class="dlomshbcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ladybird" /></template>
