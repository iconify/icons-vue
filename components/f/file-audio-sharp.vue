<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ue2j90bzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ue2j90bzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-audio-sharp" /></template>
