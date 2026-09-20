<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlxyymbyb.css';
import '../../css/w/wgvkkuyqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vlxyymbyb"/><path class="wgvkkuyqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:amazon-original" /></template>
