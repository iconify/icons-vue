<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyv3t0bmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wyv3t0bmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:icicles-fence" /></template>
