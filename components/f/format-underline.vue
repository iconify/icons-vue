<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jku7b4b9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jku7b4b9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:format-underline" /></template>
