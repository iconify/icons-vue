<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/re9t7ccrz.css';
import '../../css/x/xd65xdbvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":726,"height":726};
const content = `<path class="re9t7ccrz"/><path class="xd65xdbvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:it-tools" /></template>
