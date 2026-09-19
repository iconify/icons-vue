<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdl1zucwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kdl1zucwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:folder-open-solid" /></template>
