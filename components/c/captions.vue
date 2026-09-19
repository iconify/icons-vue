<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fivtkccbu.css';
import '../../css/b/b1ecs5fbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fivtkccbu"/><path class="b1ecs5fbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:captions" /></template>
