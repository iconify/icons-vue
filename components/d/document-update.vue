<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h0s08bcuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h0s08bcuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:document-update" /></template>
