<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3c2rj_zs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k3c2rj_zs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-u-turn-left-sharp-duotone" /></template>
