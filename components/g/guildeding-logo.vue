<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qm9mszbfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qm9mszbfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:guildeding-logo" /></template>
