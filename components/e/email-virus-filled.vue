<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u67vq-k0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u67vq-k0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:email-virus-filled" /></template>
