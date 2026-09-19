<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hi9xizbjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="hi9xizbjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:livewire-wordmark" /></template>
