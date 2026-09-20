<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bchgr6kwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bchgr6kwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:googlecloudstorage" /></template>
