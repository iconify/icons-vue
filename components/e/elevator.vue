<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9zj8hbor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w9zj8hbor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:elevator" /></template>
