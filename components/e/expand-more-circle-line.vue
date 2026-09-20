<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flzdmo7bc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="flzdmo7bc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:expand-more-circle-line" /></template>
