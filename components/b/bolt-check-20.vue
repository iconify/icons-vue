<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9dzyiszx.css';
import '../../css/g/g8-7we8zc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v9dzyiszx"/><path class="g8-7we8zc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bolt-check-20" /></template>
