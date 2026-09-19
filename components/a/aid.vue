<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s772zd-8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s772zd-8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:aid" /></template>
