<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhyzjr1yy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="bhyzjr1yy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-ten-filled" /></template>
