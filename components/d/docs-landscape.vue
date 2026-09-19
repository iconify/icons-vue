<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5bs2jbns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":989,"height":1000};
const content = `<path class="t5bs2jbns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:docs-landscape" /></template>
