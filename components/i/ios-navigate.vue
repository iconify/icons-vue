<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6d2jrb7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b6d2jrb7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-navigate" /></template>
