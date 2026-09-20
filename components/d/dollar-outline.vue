<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i923-abes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="i923-abes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:dollar-outline" /></template>
