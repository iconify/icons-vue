<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9on-9b5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="d9on-9b5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:cherry-pick-commit" /></template>
