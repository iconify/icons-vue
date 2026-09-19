<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p78tgrw2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p78tgrw2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:ice-cream" /></template>
