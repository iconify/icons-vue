<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/na8gr4b-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="na8gr4b-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:game-die" /></template>
