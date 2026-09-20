<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ev03z9c2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ev03z9c2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circuit-ground" /></template>
