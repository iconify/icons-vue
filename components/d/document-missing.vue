<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sast5uygs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sast5uygs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:document-missing" /></template>
