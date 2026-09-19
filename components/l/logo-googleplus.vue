<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zkqi2gdoy.css';
import '../../css/w/waq35gbzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zkqi2gdoy"/><path class="waq35gbzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:logo-googleplus" /></template>
