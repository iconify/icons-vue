<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9lzej0dp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="b9lzej0dp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:building-alt1-11" /></template>
