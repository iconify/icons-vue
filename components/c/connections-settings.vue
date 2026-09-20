<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4qr7wbws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="b4qr7wbws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:connections-settings" /></template>
