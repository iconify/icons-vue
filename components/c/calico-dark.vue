<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhwetz1ra.css';
import '../../css/e/ep2grliyt.css';
import '../../css/t/t1d4nlbha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rhwetz1ra"/><path class="ep2grliyt"/><path class="t1d4nlbha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:calico-dark" /></template>
