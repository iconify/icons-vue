<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtpeb-edw.css';
import '../../css/m/mq2ccos5s.css';
import '../../css/w/wh25rpwfz.css';
import '../../css/u/us0mlcc8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xtpeb-edw"><path class="mq2ccos5s"/><path clip-rule="evenodd" class="wh25rpwfz"/></g><path clip-rule="evenodd" class="us0mlcc8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:folder-search-duotone" /></template>
