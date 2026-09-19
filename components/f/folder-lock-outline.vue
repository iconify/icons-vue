<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lc0el9bce.css';
import '../../css/r/r8s95ubha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lc0el9bce"/><path class="r8s95ubha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:folder-lock-outline" /></template>
