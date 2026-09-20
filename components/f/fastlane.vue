<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9pwg9s4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x9pwg9s4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:fastlane" /></template>
