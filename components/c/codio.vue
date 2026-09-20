<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aoihrz1aq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aoihrz1aq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:codio" /></template>
