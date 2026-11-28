<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2hxlwb9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b2hxlwb9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:droplet-plus" /></template>
