<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/liy6tw56v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="liy6tw56v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:facebook-fill" /></template>
