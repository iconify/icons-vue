<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl1efpbyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yl1efpbyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:left-to-right-list-triangle" /></template>
