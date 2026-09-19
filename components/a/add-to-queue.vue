<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbddd627w.css';
import '../../css/p/pia7y9bjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hbddd627w"/><path class="pia7y9bjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:add-to-queue" /></template>
