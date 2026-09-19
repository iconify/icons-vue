<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovmiey8oy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ovmiey8oy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:location-pin-off-filled" /></template>
