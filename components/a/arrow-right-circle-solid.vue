<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kiayg_b0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kiayg_b0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:arrow-right-circle-solid" /></template>
