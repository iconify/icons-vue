<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d00cz4bxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d00cz4bxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:drag-squares-vertical-solid" /></template>
