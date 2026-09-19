<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkyt__bov.css';
import '../../css/y/yerm5_p6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jkyt__bov"/><path clip-rule="evenodd" class="yerm5_p6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:gamepad-outline" /></template>
