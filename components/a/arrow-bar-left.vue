<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfx2zdb7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gfx2zdb7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-bar-left" /></template>
