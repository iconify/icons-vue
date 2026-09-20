<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skeod9bve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="skeod9bve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:film-frame" /></template>
