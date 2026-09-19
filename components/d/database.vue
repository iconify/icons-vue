<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iskbth2oq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iskbth2oq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:database" /></template>
