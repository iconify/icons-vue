<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j284f22vx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j284f22vx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:first-bracket" /></template>
