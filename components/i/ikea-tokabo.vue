<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsytlubgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rsytlubgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ikea-tokabo" /></template>
