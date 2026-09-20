<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hi0mne.css';
import '../../css/s/so-from-60.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hi0mne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:circle" /></template>
