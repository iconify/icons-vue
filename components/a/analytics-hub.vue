<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnn_acbmc.css';
import '../../css/l/lrp6bibkl.css';
import '../../css/c/c-9udcc7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bnn_acbmc"/><path class="lrp6bibkl"/><path class="c-9udcc7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:analytics-hub" /></template>
