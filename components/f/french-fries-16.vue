<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4rzdlm4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="b4rzdlm4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:french-fries-16" /></template>
