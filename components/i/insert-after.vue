<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9ds4yb2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r9ds4yb2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:insert-after" /></template>
