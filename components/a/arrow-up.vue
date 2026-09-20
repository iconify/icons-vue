<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/metg5eb8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="metg5eb8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-up" /></template>
