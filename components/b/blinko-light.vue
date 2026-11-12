<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nq_n93buh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nq_n93buh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:blinko-light" /></template>
