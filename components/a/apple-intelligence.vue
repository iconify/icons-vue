<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sf-gykbkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sf-gykbkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:apple-intelligence" /></template>
