<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swjyrsbvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="swjyrsbvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:battery-charging-16-solid" /></template>
