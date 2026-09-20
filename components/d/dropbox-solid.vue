<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tgam3xbki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tgam3xbki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:dropbox-solid" /></template>
