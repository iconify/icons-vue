<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-8zrhbdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="w-8zrhbdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-down-16-solid" /></template>
