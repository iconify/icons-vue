<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbgoen-2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nbgoen-2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:healthcare-nlp-api" /></template>
