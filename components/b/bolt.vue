<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kl7_lacbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kl7_lacbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:bolt" /></template>
