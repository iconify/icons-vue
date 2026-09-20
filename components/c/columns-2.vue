<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m41pis-hp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m41pis-hp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:columns-2" /></template>
