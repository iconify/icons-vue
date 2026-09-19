<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a06a5jfuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="a06a5jfuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:folder-fill" /></template>
