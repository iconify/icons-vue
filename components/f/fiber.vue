<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fr_dud7lz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fr_dud7lz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:fiber" /></template>
