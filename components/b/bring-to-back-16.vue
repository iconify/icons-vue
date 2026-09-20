<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjnuvrbls.css';
import '../../css/o/oco7h52sv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="cjnuvrbls"/><path class="oco7h52sv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:bring-to-back-16" /></template>
