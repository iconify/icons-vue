<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fehduy9qf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fehduy9qf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:chair-one" /></template>
