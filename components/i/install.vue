<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz44lebrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nz44lebrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:install" /></template>
