<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yle_ezbbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yle_ezbbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:badger" /></template>
