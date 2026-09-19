<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbiw0ob-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qbiw0ob-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:bookmark-add" /></template>
