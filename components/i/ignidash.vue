<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tc_p19a1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tc_p19a1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ignidash" /></template>
