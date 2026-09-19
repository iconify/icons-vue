<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yz4dern3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yz4dern3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ikea-floalt-panel" /></template>
