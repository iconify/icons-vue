<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nm_lsjb3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nm_lsjb3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:devpost" /></template>
