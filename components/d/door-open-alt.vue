<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8ha2hsdr.css';
import '../../css/a/aby3u3bop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f8ha2hsdr"/><path class="aby3u3bop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:door-open-alt" /></template>
