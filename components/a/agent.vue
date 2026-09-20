<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjd5j7bep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="vjd5j7bep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:agent" /></template>
