<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emylgjb0y.css';
import '../../css/r/rbak6zq5p.css';
import '../../css/z/zxys3pw6q.css';
import '../../css/z/zkwmf0bbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs/><path class="emylgjb0y"/><path class="rbak6zq5p"/><path class="zxys3pw6q"/><path class="zkwmf0bbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:barrier" /></template>
