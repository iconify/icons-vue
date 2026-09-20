<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgpeqgbme.css';
import '../../css/b/bsih12bdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xgpeqgbme"/><path class="bsih12bdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:cursor-arrow-duotone" /></template>
