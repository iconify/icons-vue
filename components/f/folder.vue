<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s86b8cbde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s86b8cbde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:folder" /></template>
