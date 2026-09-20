<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_p2kezbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_p2kezbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:call-off-filled" /></template>
