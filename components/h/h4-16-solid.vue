<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ei424mv-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ei424mv-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:h4-16-solid" /></template>
