<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2k9q-bar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q2k9q-bar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:alt-arrow-down-outline" /></template>
