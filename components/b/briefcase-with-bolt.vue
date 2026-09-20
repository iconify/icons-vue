<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hj7d2mlel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hj7d2mlel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:briefcase-with-bolt" /></template>
