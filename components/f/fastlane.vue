<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egtzl_b-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="egtzl_b-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:fastlane" /></template>
