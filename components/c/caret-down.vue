<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmrc8zbxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmrc8zbxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:caret-down" /></template>
