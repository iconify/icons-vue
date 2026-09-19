<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjwaosbwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vjwaosbwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chevron-left-small-filled" /></template>
