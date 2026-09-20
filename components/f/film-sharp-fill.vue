<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h52a2qe1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h52a2qe1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:film-sharp-fill" /></template>
