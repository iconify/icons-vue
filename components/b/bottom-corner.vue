<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv22lubiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sv22lubiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:bottom-corner" /></template>
