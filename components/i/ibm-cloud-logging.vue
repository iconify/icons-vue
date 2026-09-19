<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lm_s39bqo.css';
import '../../css/b/bf32wh85n.css';
import '../../css/l/li_wjjrfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lm_s39bqo"/><path class="bf32wh85n"/><path class="li_wjjrfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-cloud-logging" /></template>
