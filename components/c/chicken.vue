<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wso6qqzcb.css';
import '../../css/u/u9-cdnbkn.css';
import '../../css/e/e3fjlzrkz.css';
import '../../css/r/r3vrbgbgv.css';
import '../../css/e/e7nts4gnf.css';
import '../../css/y/ylcvhwbrw.css';
import '../../css/q/qxlid6bxk.css';
import '../../css/r/ro9rytf_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="wso6qqzcb"/><path class="u9-cdnbkn"/><path class="e3fjlzrkz"/><path class="r3vrbgbgv"/><circle class="e7nts4gnf"/><circle class="ylcvhwbrw"/><path class="qxlid6bxk"/><path class="ro9rytf_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:chicken" /></template>
