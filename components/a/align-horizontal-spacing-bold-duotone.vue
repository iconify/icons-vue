<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewu5_fbdb.css';
import '../../css/g/g4sooab0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ewu5_fbdb"/><path class="g4sooab0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:align-horizontal-spacing-bold-duotone" /></template>
