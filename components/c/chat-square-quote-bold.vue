<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1two7b3n.css';
import '../../css/c/cwkqqicwy.css';
import '../../css/r/rgklaf5rc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1two7b3n"/><path class="cwkqqicwy"/><path clip-rule="evenodd" class="rgklaf5rc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-square-quote-bold" /></template>
