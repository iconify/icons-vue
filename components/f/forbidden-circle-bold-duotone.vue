<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwnu8vvwz.css';
import '../../css/a/ah0oz-g8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jwnu8vvwz"/><path class="ah0oz-g8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:forbidden-circle-bold-duotone" /></template>
