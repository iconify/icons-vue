<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/w/wj-7246uw.css';
import '../../css/b/bj6jcvcoq.css';
import '../../css/y/y2h8hf9bi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="circleFlagsDv0"><circle class="bc1fd0lxe"/></mask><g mask="url(#circleFlagsDv0)"><path class="wj-7246uw"/><path class="bj6jcvcoq"/><path class="y2h8hf9bi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:dv" /></template>
