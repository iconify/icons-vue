<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oazie5qav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="oazie5qav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:inbox-arrow-up-16-solid" /></template>
