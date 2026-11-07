<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fi6qtibex.css';
import '../../css/s/s02o69bfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fi6qtibex"/><path class="s02o69bfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:call-dropped-rounded-bold-duotone" /></template>
