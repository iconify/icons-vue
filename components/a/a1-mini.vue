<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trw6j0drs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="trw6j0drs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:a1-mini" /></template>
