<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7wdd3v4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="v7wdd3v4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:eyeos" /></template>
