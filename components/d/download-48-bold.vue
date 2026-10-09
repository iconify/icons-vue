<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5llwvbom.css';
import '../../css/z/z9zjvabag.css';
import '../../css/r/r1bpb3k0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g5llwvbom"/><path class="z9zjvabag"/><path class="r1bpb3k0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:download-48-bold" /></template>
