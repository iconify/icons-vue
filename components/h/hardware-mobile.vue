<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7jc9sb_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h7jc9sb_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:hardware-mobile" /></template>
