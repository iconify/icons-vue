<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pawv7tbbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pawv7tbbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:dna-solid" /></template>
