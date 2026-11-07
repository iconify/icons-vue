<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yu1bol9do.css';
import '../../css/c/crtuvabgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yu1bol9do"/><path class="crtuvabgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:align-vertical-spacing-bold-duotone" /></template>
