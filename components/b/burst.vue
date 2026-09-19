<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzz-pgc8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rzz-pgc8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:burst" /></template>
