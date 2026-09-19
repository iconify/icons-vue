<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4vyfl95a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4vyfl95a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:announcement" /></template>
