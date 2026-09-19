<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7izuqw-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b7izuqw-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:caret-left-circle" /></template>
