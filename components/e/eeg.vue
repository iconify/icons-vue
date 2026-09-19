<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtgiu4vpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xtgiu4vpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:eeg" /></template>
