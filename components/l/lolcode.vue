<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4ztfc8fc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":411,"height":512};
const content = `<path class="d4ztfc8fc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:lolcode" /></template>
