<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxjnfe56w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sxjnfe56w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:folder-edit-filled" /></template>
