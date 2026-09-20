<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbweo4b2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jbweo4b2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-big-up-sharp-duotone" /></template>
