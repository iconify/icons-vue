<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovis36bqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ovis36bqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:high-voltage" /></template>
