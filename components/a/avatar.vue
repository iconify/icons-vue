<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4pew8t4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="z4pew8t4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:avatar" /></template>
