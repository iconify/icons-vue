<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0y3bjbie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="b0y3bjbie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:add-phone" /></template>
