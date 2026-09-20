<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/livtncc2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="livtncc2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:arrow-button-up" /></template>
