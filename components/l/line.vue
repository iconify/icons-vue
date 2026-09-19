<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sypwx4bcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="sypwx4bcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:line" /></template>
