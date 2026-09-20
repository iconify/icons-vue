<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ii82hnrhg.css';
import '../../css/y/y0rh9nbet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<path class="ii82hnrhg"/><path clip-rule="evenodd" class="y0rh9nbet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:cloud-bolt-1" /></template>
