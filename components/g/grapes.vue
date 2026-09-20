<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzp0vrb8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dzp0vrb8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:grapes" /></template>
