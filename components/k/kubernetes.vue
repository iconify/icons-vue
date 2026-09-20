<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ix-pf_jrx.css';
import '../../css/r/r3q5yh9_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ix-pf_jrx"/><path class="r3q5yh9_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kubernetes" /></template>
