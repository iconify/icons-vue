<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ws80ii3ha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ws80ii3ha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:buildings-2" /></template>
