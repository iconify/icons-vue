<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajbt87aul.css';
import '../../css/b/bjh1ltbve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ajbt87aul"/><path class="bjh1ltbve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lockbox-20-bold" /></template>
