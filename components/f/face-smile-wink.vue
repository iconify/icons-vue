<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jr5kxzb3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="jr5kxzb3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:face-smile-wink" /></template>
