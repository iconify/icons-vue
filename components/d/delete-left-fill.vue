<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/biyapqb9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="biyapqb9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:delete-left-fill" /></template>
