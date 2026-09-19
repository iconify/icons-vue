<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgpn73_gs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kgpn73_gs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:globe-americas" /></template>
