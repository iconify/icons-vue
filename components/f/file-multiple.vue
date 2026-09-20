<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eeg8hro-s.css';
import '../../css/b/b7-je_b1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eeg8hro-s"/><path class="b7-je_b1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:file-multiple" /></template>
