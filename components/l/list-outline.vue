<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttxo3u1js.css';
import '../../css/u/u99giob-v.css';
import '../../css/t/tcfp_5smf.css';
import '../../css/h/hrejwrbgb.css';
import '../../css/w/wu7c3x_tx.css';
import '../../css/d/d_mqyac1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="ttxo3u1js"/><circle class="u99giob-v"/><circle class="tcfp_5smf"/><rect class="hrejwrbgb"/><rect class="wu7c3x_tx"/><rect class="d_mqyac1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:list-outline" /></template>
