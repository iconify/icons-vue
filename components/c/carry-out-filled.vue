<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/or5g61b_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="or5g61b_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:carry-out-filled" /></template>
