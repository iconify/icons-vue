<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/klqzlfb6u.css';
import '../../css/b/bfbxrvtsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="klqzlfb6u"/><path class="bfbxrvtsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-edit" /></template>
