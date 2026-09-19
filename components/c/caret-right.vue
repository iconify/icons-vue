<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fr-5ntbhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fr-5ntbhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:caret-right" /></template>
