<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pz7bdnbih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pz7bdnbih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:disable-bell-notification-remix" /></template>
