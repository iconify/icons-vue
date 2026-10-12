<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yynfaacui.css';
import '../../css/g/g6pvh7b3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yynfaacui"/><path class="g6pvh7b3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:emoji-sad-stroke-20" /></template>
