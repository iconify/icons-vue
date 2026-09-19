<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/v/vuw-vtbcg.css';
import '../../css/i/ix74hpb0f.css';
import '../../css/m/mrkbx1baw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="vuw-vtbcg"/><path class="ix74hpb0f"/><path class="mrkbx1baw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:inbox-unread" /></template>
