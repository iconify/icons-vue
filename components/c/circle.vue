<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zj51rsh9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="zj51rsh9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:circle" /></template>
