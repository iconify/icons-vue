<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ic6i11b1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ic6i11b1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:deepgram" /></template>
