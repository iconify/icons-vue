<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uob4j6bcx.css';
import '../../css/j/jog-_gb5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uob4j6bcx"/><path class="jog-_gb5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:folder-heart-filled" /></template>
