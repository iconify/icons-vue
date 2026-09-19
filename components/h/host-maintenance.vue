<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fno-s8bqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fno-s8bqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:host-maintenance" /></template>
