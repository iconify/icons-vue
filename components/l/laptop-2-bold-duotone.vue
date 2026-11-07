<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yr-pw-b8g.css';
import '../../css/s/s2urmqbds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yr-pw-b8g"/><path class="s2urmqbds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:laptop-2-bold-duotone" /></template>
