<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqir62biz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="bqir62biz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:cyborg-2-remix" /></template>
