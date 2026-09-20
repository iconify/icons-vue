<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tw9vr5bmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tw9vr5bmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:flathub-light" /></template>
