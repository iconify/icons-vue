<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q__ikjbpe.css';
import '../../css/z/z9e9gnbvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q__ikjbpe"/><path class="z9e9gnbvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-voice" /></template>
