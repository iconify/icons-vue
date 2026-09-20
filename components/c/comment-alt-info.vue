<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4nto2o6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4nto2o6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:comment-alt-info" /></template>
