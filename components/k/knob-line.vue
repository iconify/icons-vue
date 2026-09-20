<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwowkw2ww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cwowkw2ww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:knob-line" /></template>
