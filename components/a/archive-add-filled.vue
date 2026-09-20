<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-y5yjkuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-y5yjkuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:archive-add-filled" /></template>
