<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gj-sx-box.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gj-sx-box"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alphabetical-variant" /></template>
