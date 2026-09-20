<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocf_5ubml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ocf_5ubml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:crowdsource" /></template>
