<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3dsu-bqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b3dsu-bqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:button-stop-bold" /></template>
