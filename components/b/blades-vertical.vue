<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lm5yj3b2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lm5yj3b2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:blades-vertical" /></template>
