<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j28zcvwzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="j28zcvwzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:fire" /></template>
