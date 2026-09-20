<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ww6kmx10n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ww6kmx10n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:art-gallery-15" /></template>
