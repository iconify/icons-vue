<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1nt6tnct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="o1nt6tnct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:communication-filled" /></template>
