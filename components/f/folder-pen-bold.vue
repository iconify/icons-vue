<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jppf41bdk.css';
import '../../css/j/j-xg48kfo.css';
import '../../css/t/tnn4k8b5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jppf41bdk"/><path class="j-xg48kfo"/><path clip-rule="evenodd" class="tnn4k8b5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-pen-bold" /></template>
