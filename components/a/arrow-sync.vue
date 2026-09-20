<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqxuadcaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mqxuadcaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:arrow-sync" /></template>
