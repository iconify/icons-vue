<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmicsu0ug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="kmicsu0ug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:alert-filled" /></template>
