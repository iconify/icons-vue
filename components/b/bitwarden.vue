<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/quiv4pbed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="quiv4pbed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:bitwarden" /></template>
