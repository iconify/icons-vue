<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nw621dqkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nw621dqkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:folder-solid" /></template>
