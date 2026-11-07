<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/conyuxbxt.css';
import '../../css/v/vlg3w9b6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="conyuxbxt"/><path class="vlg3w9b6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:armchair-bold" /></template>
