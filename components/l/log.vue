<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pd5xcgt6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pd5xcgt6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:log" /></template>
