<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqm1pugoc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uqm1pugoc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:exercism" /></template>
