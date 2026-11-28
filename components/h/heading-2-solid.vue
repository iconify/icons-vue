<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdgq2lbcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rdgq2lbcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:heading-2-solid" /></template>
