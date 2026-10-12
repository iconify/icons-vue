<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xaxmjgbje.css';
import '../../css/o/ofusmvbko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xaxmjgbje"/><path class="ofusmvbko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:file-output-filled" /></template>
