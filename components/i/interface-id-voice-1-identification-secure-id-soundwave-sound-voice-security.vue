<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ov_j_ngpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ov_j_ngpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-id-voice-1-identification-secure-id-soundwave-sound-voice-security" /></template>
