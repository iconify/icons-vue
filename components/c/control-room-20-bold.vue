<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1m8p11fi.css';
import '../../css/o/oa8orvb1f.css';
import '../../css/x/xg0hbcg2p.css';
import '../../css/o/osylfriqx.css';
import '../../css/p/p3fycvbnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d1m8p11fi"/><path class="oa8orvb1f"/><path class="xg0hbcg2p"/><path class="osylfriqx"/><path class="p3fycvbnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:control-room-20-bold" /></template>
