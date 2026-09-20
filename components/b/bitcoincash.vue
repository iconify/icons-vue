<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahqnmf6qa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ahqnmf6qa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:bitcoincash" /></template>
