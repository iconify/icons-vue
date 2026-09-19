<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twcfhpwqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="twcfhpwqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:dollar-circle-filled" /></template>
