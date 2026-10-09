<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7x7egb-c.css';
import '../../css/s/sqs8isb_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c7x7egb-c"/><path class="sqs8isb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bbq-20" /></template>
