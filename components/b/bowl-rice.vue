<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gumg3rbyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gumg3rbyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bowl-rice" /></template>
