<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocxlw5vve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ocxlw5vve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:globe" /></template>
