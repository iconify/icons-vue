<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/et74su9kq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="et74su9kq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:delete-row" /></template>
