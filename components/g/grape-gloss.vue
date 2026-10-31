<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aedgrfgit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aedgrfgit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:grape-gloss" /></template>
