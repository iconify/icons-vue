<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7575cbkw.css';
import '../../css/p/p769e2bzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="y7575cbkw"/><path class="p769e2bzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:drought-20" /></template>
