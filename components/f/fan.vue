<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_34pvbxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_34pvbxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:fan" /></template>
