<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lq4v6_btt.css';
import '../../css/n/ngrlpuxaw.css';
import '../../css/v/vzfwzhbbb.css';
import '../../css/t/t4xgpdb5d.css';
import '../../css/o/o5_0jac3d.css';
import '../../css/q/qh4l7ebfc.css';
import '../../css/p/piu34xb3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lq4v6_btt"/><path class="ngrlpuxaw"/><path class="vzfwzhbbb"/><path class="t4xgpdb5d"/><path class="o5_0jac3d"/><path class="qh4l7ebfc"/><path class="piu34xb3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-radio" /></template>
