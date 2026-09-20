<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c75g7nqit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c75g7nqit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:filter-alt-circle-solid" /></template>
