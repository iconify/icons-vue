<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/puieb1_ra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="puieb1_ra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:columns-line" /></template>
