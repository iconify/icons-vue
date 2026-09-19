<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5xks9b-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n5xks9b-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:cubes" /></template>
