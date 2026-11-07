<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/je8y-zlbu.css';
import '../../css/p/p2qbusfri.css';
import '../../css/f/fcdqs1q8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="je8y-zlbu"/><path class="p2qbusfri"/><path class="fcdqs1q8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:fog-bold" /></template>
