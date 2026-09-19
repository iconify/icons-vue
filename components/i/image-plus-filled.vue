<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-b_-kbhg.css';
import '../../css/g/gsd-3zbqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-b_-kbhg"/><path class="gsd-3zbqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:image-plus-filled" /></template>
