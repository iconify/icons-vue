<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7cmimq3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b7cmimq3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:align-right-duotone" /></template>
