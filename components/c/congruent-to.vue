<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo5re-bue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mo5re-bue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:congruent-to" /></template>
