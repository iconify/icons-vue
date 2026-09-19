<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9ohr9txj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="s9ohr9txj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:id-badge" /></template>
