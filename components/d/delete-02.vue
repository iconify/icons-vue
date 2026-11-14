<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3wr687ld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c3wr687ld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:delete-02" /></template>
