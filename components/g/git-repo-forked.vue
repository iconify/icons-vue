<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2deosl3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n2deosl3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:git-repo-forked" /></template>
