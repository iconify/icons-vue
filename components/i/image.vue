<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzljxcb6h.css';
import '../../css/l/lugjjbc-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vzljxcb6h"/><path class="lugjjbc-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:image" /></template>
