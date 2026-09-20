<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rldvznx3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rldvznx3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:googleauthenticator" /></template>
