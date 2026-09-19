<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0tl3qq7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="b0tl3qq7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:insurance-filled" /></template>
