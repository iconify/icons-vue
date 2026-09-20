<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4z_23_9n.css';
import '../../css/w/w40fbby0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="z4z_23_9n"/><path class="w40fbby0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:drum-brushes-16" /></template>
