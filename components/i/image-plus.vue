<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvz3gdbus.css';
import '../../css/m/mz1hr1bdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jvz3gdbus"/><path class="mz1hr1bdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:image-plus" /></template>
