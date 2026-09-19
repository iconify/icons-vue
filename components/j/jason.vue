<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjpv09b3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":832,"height":1024};
const content = `<path class="zjpv09b3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:jason" /></template>
