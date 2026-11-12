<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_lja2bcd.css';
import '../../css/w/wmnla3ben.css';
import '../../css/p/ppxb-5bqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="p_lja2bcd"/><path class="wmnla3ben"/><path class="ppxb-5bqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:dependabot-wordmark" /></template>
