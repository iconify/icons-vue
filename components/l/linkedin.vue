<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqt9-9byr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rqt9-9byr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:linkedin" /></template>
