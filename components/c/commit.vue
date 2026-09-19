<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qy2fjenpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":640};
const content = `<path class="qy2fjenpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:commit" /></template>
