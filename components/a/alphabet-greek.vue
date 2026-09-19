<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhpb4hb1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhpb4hb1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:alphabet-greek" /></template>
