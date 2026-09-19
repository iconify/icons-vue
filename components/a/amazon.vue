<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zm12trbwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zm12trbwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:amazon" /></template>
