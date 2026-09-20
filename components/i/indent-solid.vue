<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u67g4cbgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u67g4cbgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:indent-solid" /></template>
