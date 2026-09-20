<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4ft-0tpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="b4ft-0tpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:image-comment-light" /></template>
