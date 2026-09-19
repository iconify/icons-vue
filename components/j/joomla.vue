<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oz7f8bcqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="oz7f8bcqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:joomla" /></template>
