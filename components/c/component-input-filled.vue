<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqne-81aw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jqne-81aw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:component-input-filled" /></template>
