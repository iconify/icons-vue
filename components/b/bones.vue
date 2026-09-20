<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9slov7tl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g9slov7tl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bones" /></template>
