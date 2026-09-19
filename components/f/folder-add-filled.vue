<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjiszdb8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="cjiszdb8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:folder-add-filled" /></template>
