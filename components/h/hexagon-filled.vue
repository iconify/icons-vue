<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4v05cb7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a4v05cb7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:hexagon-filled" /></template>
