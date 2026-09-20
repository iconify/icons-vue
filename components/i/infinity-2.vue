<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1s4mhchp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o1s4mhchp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:infinity-2" /></template>
