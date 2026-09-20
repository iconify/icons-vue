<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tm0lxtbtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tm0lxtbtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lore-epic-games-light" /></template>
