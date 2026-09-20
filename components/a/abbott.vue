<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3g-2fu1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u3g-2fu1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:abbott" /></template>
