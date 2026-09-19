<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ogau4npip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ogau4npip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:folder" /></template>
