<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfeh66bby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qfeh66bby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:food" /></template>
