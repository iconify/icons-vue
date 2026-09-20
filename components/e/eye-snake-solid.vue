<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjtpl_b2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jjtpl_b2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:eye-snake-solid" /></template>
