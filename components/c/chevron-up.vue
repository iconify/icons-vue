<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mne-racvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":10,"height":16};
const content = `<path class="mne-racvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:chevron-up" /></template>
