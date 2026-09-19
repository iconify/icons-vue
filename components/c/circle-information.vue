<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9c4ytw-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c9c4ytw-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:circle-information" /></template>
