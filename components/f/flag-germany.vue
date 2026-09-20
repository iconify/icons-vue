<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dur0b2p3t.css';
import '../../css/k/kqwq9psty.css';
import '../../css/u/u9hq09b6k.css';
import '../../css/q/qy525jbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="dur0b2p3t"/><path class="kqwq9psty"/><path class="u9hq09b6k"/><path class="qy525jbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:flag-germany" /></template>
