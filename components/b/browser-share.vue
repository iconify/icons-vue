<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uijg__bke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uijg__bke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:browser-share" /></template>
