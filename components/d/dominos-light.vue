<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydzbdhtcp.css';
import '../../css/e/e5c90cc_n.css';
import '../../css/q/q_4suiuce.css';
import '../../css/x/xhh1_acdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":333.22,"height":333.22};
const content = `<path class="ydzbdhtcp"/><path class="e5c90cc_n"/><path class="q_4suiuce"/><path class="xhh1_acdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:dominos-light" /></template>
