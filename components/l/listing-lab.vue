<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ai0e078-i.css';
import '../../css/i/ipw5bzbjz.css';
import '../../css/t/twp8wbb9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ai0e078-i"/><path class="ipw5bzbjz"/><path class="twp8wbb9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:listing-lab" /></template>
