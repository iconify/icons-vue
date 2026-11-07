<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j08vyhzaj.css';
import '../../css/l/l531-vi_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j08vyhzaj"/><path class="l531-vi_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cloud-download-outline" /></template>
