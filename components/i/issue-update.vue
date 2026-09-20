<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bja4wpuww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bja4wpuww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:issue-update" /></template>
