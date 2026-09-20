<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlv6aib1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jlv6aib1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:arrow-reload-horizontal-2-flat" /></template>
