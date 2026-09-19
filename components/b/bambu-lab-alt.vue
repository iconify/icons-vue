<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdy1rebht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rdy1rebht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bambu-lab-alt" /></template>
