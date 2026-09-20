<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ay9fj-b3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ay9fj-b3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:comment-16" /></template>
