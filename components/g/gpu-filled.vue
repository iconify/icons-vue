<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkeen_bhs.css';
import '../../css/f/f583e5b1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jkeen_bhs"/><path clip-rule="evenodd" class="f583e5b1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:gpu-filled" /></template>
