<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/an6bpbblv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="an6bpbblv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:chevron-right-left-16-solid" /></template>
