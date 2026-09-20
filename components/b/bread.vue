<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrlu5ccyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hrlu5ccyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bread" /></template>
