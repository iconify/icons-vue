<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lj_39l2dc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lj_39l2dc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:hashtag" /></template>
