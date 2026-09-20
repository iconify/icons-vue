<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcqo08b7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rcqo08b7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:briefcase-detailed-line" /></template>
