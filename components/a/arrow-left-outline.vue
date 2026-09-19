<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4wm5dt-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="z4wm5dt-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:arrow-left-outline" /></template>
