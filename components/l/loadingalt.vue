<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6_6esb3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="f6_6esb3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:loadingalt" /></template>
