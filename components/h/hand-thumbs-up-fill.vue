<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkk31pxxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kkk31pxxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:hand-thumbs-up-fill" /></template>
