<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1nc17b8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1nc17b8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:flow-branch-line" /></template>
