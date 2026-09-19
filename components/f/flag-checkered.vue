<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1v8db0po.css';
import '../../css/b/bo9dr7buy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1v8db0po"/><path class="bo9dr7buy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:flag-checkered" /></template>
