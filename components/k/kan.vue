<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxr4hec5a.css';
import '../../css/z/zwxltobxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uxr4hec5a"/><path class="zwxltobxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kan" /></template>
