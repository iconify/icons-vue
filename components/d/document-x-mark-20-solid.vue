<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4zwxpbcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="y4zwxpbcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:document-x-mark-20-solid" /></template>
