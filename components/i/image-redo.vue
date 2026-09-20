<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q20fa9mbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q20fa9mbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:image-redo" /></template>
