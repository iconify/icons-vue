<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i04yw6bfv.css';
import '../../css/i/ifilulb6g.css';
import '../../css/b/b1ecs5fbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="i04yw6bfv"/><path class="ifilulb6g"/><path class="b1ecs5fbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-credit-card-alt" /></template>
