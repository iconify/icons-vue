<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxn8fwn7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxn8fwn7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:logs-solid" /></template>
