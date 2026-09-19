<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghg5mfmuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ghg5mfmuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:arte" /></template>
