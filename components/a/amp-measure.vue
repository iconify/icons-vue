<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-s3pyccr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-s3pyccr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:amp-measure" /></template>
