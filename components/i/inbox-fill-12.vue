<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ja5incaal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ja5incaal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:inbox-fill-12" /></template>
