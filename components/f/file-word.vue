<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ja9avj50u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ja9avj50u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:file-word" /></template>
