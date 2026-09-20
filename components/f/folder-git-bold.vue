<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v819m1itl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v819m1itl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-git-bold" /></template>
