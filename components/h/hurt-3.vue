<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7goi0bav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b7goi0bav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:hurt-3" /></template>
