<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkeom7bum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jkeom7bum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:expand-diagonal-fill" /></template>
