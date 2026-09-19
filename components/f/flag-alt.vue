<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6v9nvrha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6v9nvrha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:flag-alt" /></template>
