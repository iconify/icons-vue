<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehd_9cxzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ehd_9cxzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:lettered-list-16-solid" /></template>
