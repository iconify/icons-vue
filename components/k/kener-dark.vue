<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkagmo7rc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pkagmo7rc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kener-dark" /></template>
