<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcj6n3sgd.css';
import '../../css/f/f2--itp1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xcj6n3sgd"/><path class="f2--itp1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-pack-48-bold" /></template>
