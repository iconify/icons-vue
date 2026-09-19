<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3bjtti7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a3bjtti7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:bell" /></template>
