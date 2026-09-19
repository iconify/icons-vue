<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjonbacvn.css';
import '../../css/c/cfprd2egi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vjonbacvn"/><path class="cfprd2egi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:information-sharp" /></template>
