<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9gp-ygyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g9gp-ygyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:bucket" /></template>
