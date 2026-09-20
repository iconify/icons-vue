<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjghndu3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jjghndu3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:beaker-plus" /></template>
