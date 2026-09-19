<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/da6e7c_me.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="da6e7c_me"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:file-import" /></template>
