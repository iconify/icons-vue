<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fx6ck3egz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="fx6ck3egz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:buddy" /></template>
