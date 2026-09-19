<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qezs7ccgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qezs7ccgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:lightning" /></template>
