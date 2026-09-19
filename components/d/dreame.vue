<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6i0klbml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x6i0klbml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:dreame" /></template>
