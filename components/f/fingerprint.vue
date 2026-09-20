<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/alp38nfup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="alp38nfup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:fingerprint" /></template>
