<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gykvj3bkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gykvj3bkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:fork-knife-16-solid" /></template>
