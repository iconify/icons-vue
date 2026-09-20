<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcykceb4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rcykceb4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:health-care-2-flat" /></template>
