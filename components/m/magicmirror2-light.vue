<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmm6tlmsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nmm6tlmsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:magicmirror2-light" /></template>
