<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fr6fopb3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fr6fopb3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:alarm-clock" /></template>
