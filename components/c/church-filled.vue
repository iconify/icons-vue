<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-ggtpb7h.css';
import '../../css/o/ojum2hmgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-ggtpb7h"/><path class="ojum2hmgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:church-filled" /></template>
