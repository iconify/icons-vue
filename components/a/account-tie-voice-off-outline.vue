<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/timsxcbvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="timsxcbvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:account-tie-voice-off-outline" /></template>
