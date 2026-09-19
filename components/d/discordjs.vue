<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqx1id87h.css';
import '../../css/z/zo3ccobrl.css';
import '../../css/r/r2gi9h8in.css';
import '../../css/f/f_3ah1bgm.css';
import '../../css/p/pof1jml4s.css';
import '../../css/g/g3ylqubgx.css';
import '../../css/l/lvxyvj_du.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="uqx1id87h"/><path class="zo3ccobrl"/><path class="r2gi9h8in"/><path class="f_3ah1bgm"/><path class="pof1jml4s"/><path class="g3ylqubgx"/><path class="lvxyvj_du"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:discordjs" /></template>
