<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyh-ry88k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vyh-ry88k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:chevron-up-down-16-solid" /></template>
