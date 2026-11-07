<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g48ucxnqe.css';
import '../../css/i/im3g8pbea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g48ucxnqe"/><path class="im3g8pbea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hourglass-bold-duotone" /></template>
