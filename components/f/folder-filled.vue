<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jur25dbja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="jur25dbja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:folder-filled" /></template>
