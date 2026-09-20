<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fr_r5vbye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="fr_r5vbye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:crop-solid" /></template>
