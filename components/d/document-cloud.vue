<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iq5p0jpjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iq5p0jpjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:document-cloud" /></template>
