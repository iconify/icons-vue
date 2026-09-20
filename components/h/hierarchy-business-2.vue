<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ur0h5ubxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ur0h5ubxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:hierarchy-business-2" /></template>
