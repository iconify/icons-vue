<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jr1lh7bho.css';
import '../../css/v/v_uokybhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jr1lh7bho"/><path class="v_uokybhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:copy-list" /></template>
