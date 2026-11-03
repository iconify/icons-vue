<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ib8logbhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ib8logbhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:anchor-16-solid" /></template>
