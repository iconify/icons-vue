<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5hbqzbay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":860,"height":654};
const content = `<path class="b5hbqzbay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:m" /></template>
