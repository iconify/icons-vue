<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrvkwrb7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="zrvkwrb7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:ipod" /></template>
