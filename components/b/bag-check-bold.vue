<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pih1z72mh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pih1z72mh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bag-check-bold" /></template>
