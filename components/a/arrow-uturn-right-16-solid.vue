<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sw_9so7zi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="sw_9so7zi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-uturn-right-16-solid" /></template>
