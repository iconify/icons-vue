<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mh4wrolxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":480,"height":512};
const content = `<path class="mh4wrolxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:bonnet" /></template>
