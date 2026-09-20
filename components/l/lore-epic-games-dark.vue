<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihhxc7j7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ihhxc7j7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lore-epic-games-dark" /></template>
