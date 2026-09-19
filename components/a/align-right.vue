<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdue1gb9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="tdue1gb9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:align-right" /></template>
