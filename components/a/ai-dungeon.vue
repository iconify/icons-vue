<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rh_4fdb0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rh_4fdb0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:ai-dungeon" /></template>
