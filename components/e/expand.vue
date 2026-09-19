<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1sa6_p6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b1sa6_p6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:expand" /></template>
