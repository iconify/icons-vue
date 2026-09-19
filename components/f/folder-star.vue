<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmmy2rb5f.css';
import '../../css/c/ctj1h6tdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nmmy2rb5f"/><path class="ctj1h6tdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:folder-star" /></template>
