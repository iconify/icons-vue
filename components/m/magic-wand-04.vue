<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ag2u3nb2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ag2u3nb2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:magic-wand-04" /></template>
