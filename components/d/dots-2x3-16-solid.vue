<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjgd94-9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pjgd94-9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:dots-2x3-16-solid" /></template>
