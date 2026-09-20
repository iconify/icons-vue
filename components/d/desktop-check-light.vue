<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/th5wqpzfa.css';
import '../../css/v/v419d9bma.css';
import '../../css/e/ekturubtg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="th5wqpzfa"/><path clip-rule="evenodd" class="v419d9bma"/><path class="ekturubtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:desktop-check-light" /></template>
