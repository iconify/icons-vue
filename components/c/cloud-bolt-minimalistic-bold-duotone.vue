<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxvd-g65l.css';
import '../../css/s/srdp-xb5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxvd-g65l"/><path clip-rule="evenodd" class="srdp-xb5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cloud-bolt-minimalistic-bold-duotone" /></template>
