<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zd1ch4bgm.css';
import '../../css/l/l_tzrhbkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zd1ch4bgm"/><path class="l_tzrhbkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:diagram-down-bold-duotone" /></template>
