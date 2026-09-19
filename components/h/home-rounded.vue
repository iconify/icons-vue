<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svdexnquw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="svdexnquw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:home-rounded" /></template>
