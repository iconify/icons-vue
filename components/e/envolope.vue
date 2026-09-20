<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glkwmi0vq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="glkwmi0vq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:envolope" /></template>
