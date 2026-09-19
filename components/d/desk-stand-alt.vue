<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rth3cbbbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rth3cbbbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:desk-stand-alt" /></template>
