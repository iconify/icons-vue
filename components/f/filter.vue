<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jerku_bsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jerku_bsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:filter" /></template>
