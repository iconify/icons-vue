<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1m411eeg.css';
import '../../css/x/x4pv4iirw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k1m411eeg"/><path class="x4pv4iirw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:cost" /></template>
