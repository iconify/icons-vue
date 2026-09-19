<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpwk--bfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tpwk--bfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:down-left-2-short-arrow" /></template>
