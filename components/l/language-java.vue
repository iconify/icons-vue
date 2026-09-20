<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3kqooy-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c3kqooy-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:language-java" /></template>
