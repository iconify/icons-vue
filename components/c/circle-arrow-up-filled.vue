<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgrnb3bhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cgrnb3bhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-arrow-up-filled" /></template>
