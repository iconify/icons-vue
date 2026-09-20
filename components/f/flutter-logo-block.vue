<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-3qc_bhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q-3qc_bhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:flutter-logo-block" /></template>
