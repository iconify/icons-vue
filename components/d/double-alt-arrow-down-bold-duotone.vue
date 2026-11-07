<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sownw2b9k.css';
import '../../css/e/e-elr2cua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sownw2b9k"/><path clip-rule="evenodd" class="e-elr2cua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:double-alt-arrow-down-bold-duotone" /></template>
