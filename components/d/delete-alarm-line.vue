<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvkmyfbgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mvkmyfbgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:delete-alarm-line" /></template>
