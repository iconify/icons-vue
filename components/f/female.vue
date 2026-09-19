<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgzpk6fcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":1024};
const content = `<path class="rgzpk6fcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:female" /></template>
