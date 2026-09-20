<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9k1dtb8p.css';
import '../../css/s/sn4crhb1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f9k1dtb8p"/><path clip-rule="evenodd" class="sn4crhb1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:magic-hat-line" /></template>
