<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdv0gpomk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mdv0gpomk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-right-up-broken" /></template>
