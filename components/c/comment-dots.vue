<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dftf9rvck.css';
import '../../css/y/yin69t93p.css';
import '../../css/s/stjv0pdcv.css';
import '../../css/a/a11bti4rf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="dftf9rvck"/><path class="yin69t93p"/><circle class="stjv0pdcv"/><circle class="a11bti4rf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:comment-dots" /></template>
