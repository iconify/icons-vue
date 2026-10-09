<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9h1iuz6i.css';
import '../../css/z/zaaag60jr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k9h1iuz6i"/><path class="zaaag60jr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:iron-48" /></template>
