<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kl0u2jb5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kl0u2jb5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:circle-half-full-solid" /></template>
