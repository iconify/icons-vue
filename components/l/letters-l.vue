<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjdndpb3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kjdndpb3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:letters-l" /></template>
