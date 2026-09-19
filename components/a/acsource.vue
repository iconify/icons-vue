<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb6jb7bif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="tb6jb7bif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:acsource" /></template>
