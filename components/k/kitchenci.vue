<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ziyuc4lfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":476,"height":512};
const content = `<path class="ziyuc4lfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:kitchenci" /></template>
