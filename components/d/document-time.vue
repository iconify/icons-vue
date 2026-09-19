<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqi66yb-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jqi66yb-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:document-time" /></template>
