<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixy4shbxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixy4shbxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:heading-h2" /></template>
