<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dnxvm84ko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dnxvm84ko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bookmark-circle-outline" /></template>
