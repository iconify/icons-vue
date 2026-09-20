<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjvwrvb1c.css';
import '../../css/j/jobtlp51p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vjvwrvb1c"/><path class="jobtlp51p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:git-pages" /></template>
