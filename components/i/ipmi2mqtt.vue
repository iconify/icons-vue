<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hr2wg2aed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hr2wg2aed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ipmi2mqtt" /></template>
