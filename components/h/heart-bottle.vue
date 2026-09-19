<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brw53hbng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="brw53hbng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:heart-bottle" /></template>
