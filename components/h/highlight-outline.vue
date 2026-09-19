<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o860jlbvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="o860jlbvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:highlight-outline" /></template>
