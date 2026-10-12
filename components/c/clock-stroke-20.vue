<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yynfaacui.css';
import '../../css/w/wyyg1obun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yynfaacui"/><path class="wyyg1obun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:clock-stroke-20" /></template>
