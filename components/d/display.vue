<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pl-__wjru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="pl-__wjru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:display" /></template>
