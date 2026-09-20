<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9q0xo4ir.css';
import '../../css/g/gnncr1dzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q9q0xo4ir"/><path class="gnncr1dzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:eql" /></template>
