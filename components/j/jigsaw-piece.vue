<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozrj7jdhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ozrj7jdhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:jigsaw-piece" /></template>
