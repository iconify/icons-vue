<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lrcgrxwzk.css';
import '../../css/d/d79oyzb2x.css';
import '../../css/d/d1ym2h3ya.css';
import '../../css/x/xp11q_bwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lrcgrxwzk"/><circle class="d79oyzb2x"/><circle class="d1ym2h3ya"/><path class="xp11q_bwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:ai-healing" /></template>
