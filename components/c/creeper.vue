<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkx4hewee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="jkx4hewee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:creeper" /></template>
