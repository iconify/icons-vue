<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xs51nf6pn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xs51nf6pn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:gamepad-old-bold" /></template>
