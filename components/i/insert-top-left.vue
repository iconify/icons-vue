<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ou8ds1baf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ou8ds1baf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:insert-top-left" /></template>
