<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvmbt8bye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tvmbt8bye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:herman-miller-aeron" /></template>
