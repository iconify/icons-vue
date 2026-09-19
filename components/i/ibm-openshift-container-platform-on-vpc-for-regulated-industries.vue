<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5ym2eb1u.css';
import '../../css/x/xvd21f26a.css';
import '../../css/p/pnz8p0bet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="c5ym2eb1u"/><path class="xvd21f26a"/><path class="pnz8p0bet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-openshift-container-platform-on-vpc-for-regulated-industries" /></template>
