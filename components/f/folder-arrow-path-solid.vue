<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1a9-_b5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c1a9-_b5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:folder-arrow-path-solid" /></template>
