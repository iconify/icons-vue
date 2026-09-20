<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xssa-rb2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xssa-rb2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:comic-bubble" /></template>
