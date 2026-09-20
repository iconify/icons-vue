<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1mu-v3fk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l1mu-v3fk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:crown-minimalistic-outline" /></template>
