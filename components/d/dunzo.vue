<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx87-6t2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lx87-6t2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:dunzo" /></template>
