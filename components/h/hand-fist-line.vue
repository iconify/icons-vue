<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cantr0bpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cantr0bpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hand-fist-line" /></template>
