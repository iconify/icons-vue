<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hin5qvbfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="hin5qvbfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:face-meh" /></template>
