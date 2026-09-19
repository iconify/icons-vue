<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhd26jbds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nhd26jbds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:connect" /></template>
