<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3sdo1bpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y3sdo1bpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:credit-card-accept" /></template>
