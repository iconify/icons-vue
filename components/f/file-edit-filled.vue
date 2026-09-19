<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yq715zbjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yq715zbjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:file-edit-filled" /></template>
