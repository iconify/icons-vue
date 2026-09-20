<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gluszrb1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gluszrb1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:heart" /></template>
