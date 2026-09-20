<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1fh3foma.css';
import '../../css/o/oj7hu3rce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1fh3foma"/><path class="oj7hu3rce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ccd" /></template>
