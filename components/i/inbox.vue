<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlyez0tgf.css';
import '../../css/d/doz4ehbjz.css';
import '../../css/w/wa_6v2bmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="wlyez0tgf"/><path class="doz4ehbjz"/><path class="wa_6v2bmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:inbox" /></template>
