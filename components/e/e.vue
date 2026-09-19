<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kge5ed0vm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":406,"height":512};
const content = `<path class="kge5ed0vm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:e" /></template>
