<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r24wu-b6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="r24wu-b6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:list-indent" /></template>
