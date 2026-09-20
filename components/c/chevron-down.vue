<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spfx0y4sg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="spfx0y4sg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:chevron-down" /></template>
