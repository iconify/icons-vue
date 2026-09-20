<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fuidnrg9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fuidnrg9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:apprise-light" /></template>
