<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbm1k2boy.css';
import '../../css/y/yuhrwdbjr.css';
import '../../css/z/zwtkigb0t.css';
import '../../css/l/l3bykrbye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qbm1k2boy"/><path class="yuhrwdbjr"/><path class="zwtkigb0t"/><path class="l3bykrbye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:image-open-light" /></template>
