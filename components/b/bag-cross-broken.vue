<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/dsua0qxhu.css';
import '../../css/s/sr5bgubyr.css';
import '../../css/b/buo1kubox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="dsua0qxhu"/><path class="sr5bgubyr"/><path class="buo1kubox"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bag-cross-broken" /></template>
