<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kov7snrof.css';
import '../../css/a/a076kccfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kov7snrof"/><path class="a076kccfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-review-open" /></template>
