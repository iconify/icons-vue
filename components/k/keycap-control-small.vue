<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bl3s5wbqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="bl3s5wbqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-control-small" /></template>
