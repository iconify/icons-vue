<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzkaqpb-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mzkaqpb-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:component-carousel-vertical-alt" /></template>
