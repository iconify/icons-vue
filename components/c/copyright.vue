<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xc4722a5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="xc4722a5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:copyright" /></template>
