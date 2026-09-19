<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/daoyp4bub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="daoyp4bub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:commentroundempty" /></template>
