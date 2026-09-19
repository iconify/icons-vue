<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bj6cv4bll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="bj6cv4bll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:finder" /></template>
