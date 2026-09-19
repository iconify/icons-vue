<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4v7gpb9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="o4v7gpb9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:brailled" /></template>
