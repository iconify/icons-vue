<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7ephwb-o.css';
import '../../css/p/peudg--ud.css';
import '../../css/w/wx9y-fb7s.css';
import '../../css/u/u69-q7bww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="x7ephwb-o"/><path class="peudg--ud"/><path class="wx9y-fb7s"/><path class="u69-q7bww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:india" /></template>
