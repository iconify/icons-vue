<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bohnzhp-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bohnzhp-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:car-taxi-front" /></template>
