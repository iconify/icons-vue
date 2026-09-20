<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bf22_73oq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bf22_73oq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:at-symbol-light" /></template>
