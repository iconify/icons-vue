<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6pa3e19z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="h6pa3e19z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bridge-tied-arch" /></template>
