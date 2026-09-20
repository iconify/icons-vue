<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fo_ia0bmc.css';
import '../../css/c/ctzgkpf1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fo_ia0bmc"/><path class="ctzgkpf1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:calendar-solid" /></template>
