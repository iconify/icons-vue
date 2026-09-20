<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wl8aw5blo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wl8aw5blo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:atlascloud" /></template>
