<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asu33ccus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="asu33ccus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:i18next" /></template>
