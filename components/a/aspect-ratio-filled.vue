<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/migij0m8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="migij0m8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:aspect-ratio-filled" /></template>
