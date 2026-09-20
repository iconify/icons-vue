<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pi8hjkbam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pi8hjkbam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:down-circle-outline" /></template>
