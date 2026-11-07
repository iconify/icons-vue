<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ona598gli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ona598gli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:body-shape-outline" /></template>
