<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4yl73bir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v4yl73bir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:drag-squares-vertical" /></template>
