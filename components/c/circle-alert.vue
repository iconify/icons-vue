<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-xsgj-1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-xsgj-1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:circle-alert" /></template>
