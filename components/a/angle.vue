<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o43on_1lg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="o43on_1lg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:angle" /></template>
