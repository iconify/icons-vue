<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsitdowme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lsitdowme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:contract" /></template>
