<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahnu4ffkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ahnu4ffkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:hangar" /></template>
