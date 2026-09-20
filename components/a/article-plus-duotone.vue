<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/suohx5bzk.css';
import '../../css/q/qb-wvabvh.css';
import '../../css/t/tdqb12byx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="suohx5bzk"/><path class="qb-wvabvh"/><path class="tdqb12byx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:article-plus-duotone" /></template>
