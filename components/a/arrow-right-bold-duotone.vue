<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikxnezhma.css';
import '../../css/a/ao3xg6lae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ikxnezhma"/><path class="ao3xg6lae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-right-bold-duotone" /></template>
