<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpn1mqb-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rpn1mqb-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:label" /></template>
