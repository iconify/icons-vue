<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b03t9pb-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="b03t9pb-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:lock-open" /></template>
