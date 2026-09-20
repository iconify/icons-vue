<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpn5_3yii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lpn5_3yii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:control-buttons-play-2" /></template>
