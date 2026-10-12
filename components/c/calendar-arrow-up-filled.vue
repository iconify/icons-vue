<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/geuvedbeg.css';
import '../../css/z/z1o1gjbgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="geuvedbeg"/><path class="z1o1gjbgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:calendar-arrow-up-filled" /></template>
