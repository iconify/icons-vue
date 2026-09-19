<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/np8f4rmpi.css';
import '../../css/h/haf9aeb_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="np8f4rmpi"/><path class="haf9aeb_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:hardware-chip-sharp" /></template>
