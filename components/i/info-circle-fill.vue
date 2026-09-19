<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/el2cv0b9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="el2cv0b9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:info-circle-fill" /></template>
