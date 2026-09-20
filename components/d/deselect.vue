<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zsak1b5cw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zsak1b5cw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:deselect" /></template>
