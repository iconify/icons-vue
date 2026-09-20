<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fsoqsbc0b.css';
import '../../css/l/lnu--6bbg.css';
import '../../css/k/k8u3_jxow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fsoqsbc0b"/><path class="lnu--6bbg"/><path class="k8u3_jxow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kibana" /></template>
