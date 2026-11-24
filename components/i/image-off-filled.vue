<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewyuo1s9g.css';
import '../../css/w/wvjpim6nj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ewyuo1s9g"/><path class="wvjpim6nj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:image-off-filled" /></template>
