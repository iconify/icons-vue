<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-g8-zfkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="j-g8-zfkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:cup-with-steam" /></template>
