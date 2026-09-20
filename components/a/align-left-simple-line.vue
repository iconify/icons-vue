<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqs5nfbqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqs5nfbqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:align-left-simple-line" /></template>
