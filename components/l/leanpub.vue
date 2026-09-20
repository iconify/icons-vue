<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjaa7tbpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjaa7tbpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:leanpub" /></template>
