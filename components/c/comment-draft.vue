<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxoda9rgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kxoda9rgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:comment-draft" /></template>
