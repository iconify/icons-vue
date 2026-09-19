<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ok1drzb5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="ok1drzb5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:exit" /></template>
