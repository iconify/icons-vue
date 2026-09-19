<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcpbgyiwr.css';
import '../../css/x/x71-5zqyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="rcpbgyiwr"/><path class="x71-5zqyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:cpu" /></template>
