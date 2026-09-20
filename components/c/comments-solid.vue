<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dggly8hlh.css';
import '../../css/r/r1dxseh_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dggly8hlh"/><path class="r1dxseh_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:comments-solid" /></template>
