<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcsr3ia2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="dcsr3ia2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:keyboard-wireless-2-remix" /></template>
