<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/w/wj-7246uw.css';
import '../../css/p/pi2pr_bdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGuywqVbel"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGuywqVbel)"><path class="wj-7246uw"/><path class="pi2pr_bdx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:lang-hmn" /></template>
