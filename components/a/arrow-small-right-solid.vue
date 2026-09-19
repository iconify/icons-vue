<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7id3ni7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z7id3ni7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-small-right-solid" /></template>
