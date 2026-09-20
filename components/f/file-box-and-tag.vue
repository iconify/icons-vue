<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbf9zkbix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="rbf9zkbix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:file-box-and-tag" /></template>
