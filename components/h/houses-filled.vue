<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9x3p0-sd.css';
import '../../css/q/qzhirpb7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b9x3p0-sd"/><path class="qzhirpb7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:houses-filled" /></template>
