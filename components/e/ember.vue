<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-9dwnblh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":488};
const content = `<path class="j-9dwnblh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:ember" /></template>
