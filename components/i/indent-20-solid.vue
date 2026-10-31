<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkmq96vrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="wkmq96vrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:indent-20-solid" /></template>
