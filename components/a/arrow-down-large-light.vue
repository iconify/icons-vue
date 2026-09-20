<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/voeg6obyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="voeg6obyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:arrow-down-large-light" /></template>
