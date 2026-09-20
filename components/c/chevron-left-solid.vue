<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dm7-osbse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dm7-osbse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:chevron-left-solid" /></template>
