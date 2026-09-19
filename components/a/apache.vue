<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3pyk_bub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="e3pyk_bub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:apache" /></template>
