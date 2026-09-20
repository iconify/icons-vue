<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3ym1vb4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t3ym1vb4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:check-radio-unchecked" /></template>
