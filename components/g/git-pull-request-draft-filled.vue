<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zv5racc8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zv5racc8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:git-pull-request-draft-filled" /></template>
