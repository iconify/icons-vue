<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6qqu6bfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m6qqu6bfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-cloud-outline" /></template>
