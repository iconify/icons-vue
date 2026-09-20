<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qa7jsmb7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qa7jsmb7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:fathom" /></template>
